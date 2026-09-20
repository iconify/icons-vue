<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw9o1jb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pw9o1jb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:linux-outline" /></template>

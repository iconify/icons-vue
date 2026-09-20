<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr827abeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gr827abeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:image-alt-outline" /></template>

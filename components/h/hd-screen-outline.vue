<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3kxinigq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r3kxinigq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:hd-screen-outline" /></template>

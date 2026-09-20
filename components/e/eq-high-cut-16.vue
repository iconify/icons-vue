<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig_9i2bwx.css';
import '../../css/g/gyalifbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ig_9i2bwx"/><path class="gyalifbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:eq-high-cut-16" /></template>

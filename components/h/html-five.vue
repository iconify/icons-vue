<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na37jlbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="na37jlbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:html-five" /></template>

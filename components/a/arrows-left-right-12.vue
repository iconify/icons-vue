<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbu-l00ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zbu-l00ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:arrows-left-right-12" /></template>

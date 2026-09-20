<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs5cgacrv.css';
import '../../css/o/o28durbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fs5cgacrv"/><path class="o28durbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:copy-16" /></template>

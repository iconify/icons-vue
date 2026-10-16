<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex8t8sbzj.css';
import '../../css/n/nyjz5ihhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ex8t8sbzj"/><path class="nyjz5ihhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-off-20" /></template>

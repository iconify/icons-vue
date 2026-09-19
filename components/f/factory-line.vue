<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdsarc1ua.css';
import '../../css/g/gphd1nbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="zdsarc1ua"/><path class="gphd1nbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:factory-line" /></template>

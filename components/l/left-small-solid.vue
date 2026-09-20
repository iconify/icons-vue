<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zut3d2byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zut3d2byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:left-small-solid" /></template>

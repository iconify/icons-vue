<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8u7ribjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z8u7ribjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:elevator-three-riders" /></template>

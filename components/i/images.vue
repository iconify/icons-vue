<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq9tasb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="zq9tasb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:images" /></template>

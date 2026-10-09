<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z90mb8szc.css';
import '../../css/a/a6h6rcbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z90mb8szc"/><path class="a6h6rcbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bathtub-20" /></template>

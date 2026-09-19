<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqukwx59n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pqukwx59n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:diamond-outline" /></template>

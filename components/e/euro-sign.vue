<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1nyrgbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b1nyrgbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:euro-sign" /></template>

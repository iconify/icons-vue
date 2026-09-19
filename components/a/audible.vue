<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfb0shbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="vfb0shbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:audible" /></template>

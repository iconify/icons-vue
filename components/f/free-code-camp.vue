<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwj4e391z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="hwj4e391z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:free-code-camp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm5pvq32z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mm5pvq32z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:firefox" /></template>

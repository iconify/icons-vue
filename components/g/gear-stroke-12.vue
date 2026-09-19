<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eii-1ollo.css';
import '../../css/a/ahciwmy7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="eii-1ollo"/><circle class="ahciwmy7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:gear-stroke-12" /></template>

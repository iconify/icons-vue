<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzi4bo-8z.css';
import '../../css/a/a58tyvbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fzi4bo-8z"/><path class="a58tyvbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:image-stroke-20" /></template>

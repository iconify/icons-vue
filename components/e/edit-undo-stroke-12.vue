<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyjrey-ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wyjrey-ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:edit-undo-stroke-12" /></template>

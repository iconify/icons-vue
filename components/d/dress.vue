<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrhe5acdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vrhe5acdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:dress" /></template>

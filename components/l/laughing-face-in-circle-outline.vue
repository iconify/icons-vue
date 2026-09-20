<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayo-8cbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ayo-8cbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:laughing-face-in-circle-outline" /></template>

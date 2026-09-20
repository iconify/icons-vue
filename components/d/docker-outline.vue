<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu08c4b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hu08c4b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:docker-outline" /></template>

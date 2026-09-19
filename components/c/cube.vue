<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9v12bg2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g9v12bg2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:cube" /></template>

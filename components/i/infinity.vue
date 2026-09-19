<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s90ot-1ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="s90ot-1ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:infinity" /></template>

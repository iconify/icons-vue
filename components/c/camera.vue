<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da1dk-x7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="da1dk-x7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:camera" /></template>

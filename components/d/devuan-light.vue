<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eev7bvb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eev7bvb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:devuan-light" /></template>

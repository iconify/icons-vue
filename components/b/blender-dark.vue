<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5286ob_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x5286ob_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:blender-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv3vadc1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zv3vadc1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lexware-dark" /></template>

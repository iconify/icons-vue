<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su8t33t5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1435,"height":1000};
const content = `<path class="su8t33t5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:cloud" /></template>

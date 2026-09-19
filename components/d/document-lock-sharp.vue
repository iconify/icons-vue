<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6d2y6bir.css';
import '../../css/x/x1kizjb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u6d2y6bir"/><path class="x1kizjb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:document-lock-sharp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp8f-fbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pp8f-fbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ffxf-dark" /></template>

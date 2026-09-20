<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t25bgcbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t25bgcbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:deployrr-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2priwbjg.css';
import '../../css/k/k4jeo3qws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k2priwbjg"/><path class="k4jeo3qws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:invoice" /></template>

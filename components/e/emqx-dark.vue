<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmlwj9fmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmlwj9fmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:emqx-dark" /></template>

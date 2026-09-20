<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbd7ul27k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qbd7ul27k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:checkmk-dark" /></template>

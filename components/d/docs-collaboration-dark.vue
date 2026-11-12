<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztsqtcrhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ztsqtcrhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docs-collaboration-dark" /></template>

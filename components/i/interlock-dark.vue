<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu9p88b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gu9p88b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:interlock-dark" /></template>

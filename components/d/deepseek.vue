<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iln3bfxyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iln3bfxyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:deepseek" /></template>

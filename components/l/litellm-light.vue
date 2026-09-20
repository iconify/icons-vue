<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niuq_4bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="niuq_4bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:litellm-light" /></template>

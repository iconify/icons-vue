<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5u3m-8_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d5u3m-8_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lunar-dark" /></template>

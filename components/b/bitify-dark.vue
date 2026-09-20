<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtcktwbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gtcktwbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bitify-dark" /></template>

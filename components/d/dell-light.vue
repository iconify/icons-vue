<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byhqp1buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="byhqp1buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dell-light" /></template>

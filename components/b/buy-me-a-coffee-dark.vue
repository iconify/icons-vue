<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qooepw9_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qooepw9_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:buy-me-a-coffee-dark" /></template>

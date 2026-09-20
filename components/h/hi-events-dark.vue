<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd88rekga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kd88rekga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hi-events-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pshj70bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pshj70bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bookheaven-light" /></template>

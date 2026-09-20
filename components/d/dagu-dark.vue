<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i80f-5bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i80f-5bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dagu-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp7k9wstt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qp7k9wstt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ferdium-dark" /></template>

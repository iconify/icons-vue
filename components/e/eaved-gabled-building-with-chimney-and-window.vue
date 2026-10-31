<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qph61-bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qph61-bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-gabled-building-with-chimney-and-window" /></template>

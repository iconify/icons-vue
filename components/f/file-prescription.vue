<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruoswokvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ruoswokvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-prescription" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aihtfcq2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="aihtfcq2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bookmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg9qaby-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="qg9qaby-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-medical" /></template>

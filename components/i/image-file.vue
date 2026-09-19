<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spmlq2g0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="spmlq2g0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:image-file" /></template>

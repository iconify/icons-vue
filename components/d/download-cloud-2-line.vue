<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbf4n400f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbf4n400f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:download-cloud-2-line" /></template>

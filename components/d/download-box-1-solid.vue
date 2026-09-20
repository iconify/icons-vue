<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soq9mxeph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="soq9mxeph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:download-box-1-solid" /></template>

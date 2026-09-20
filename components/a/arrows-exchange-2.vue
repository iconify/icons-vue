<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfp4l5uux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfp4l5uux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-exchange-2" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doadbp5_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doadbp5_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fine-tune-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svskq2bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="svskq2bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:lasso-tool-solid" /></template>

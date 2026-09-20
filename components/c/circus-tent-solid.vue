<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srwc6uaha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="srwc6uaha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:circus-tent-solid" /></template>

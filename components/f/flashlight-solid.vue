<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy8bqqblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qy8bqqblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:flashlight-solid" /></template>

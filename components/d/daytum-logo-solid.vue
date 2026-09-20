<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg3w45bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xg3w45bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:daytum-logo-solid" /></template>

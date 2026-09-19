<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey03wibpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ey03wibpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:hospital-circle-solid" /></template>

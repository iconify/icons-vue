<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m43v59bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m43v59bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:brightness-1-solid" /></template>

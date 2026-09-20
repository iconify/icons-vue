<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmi-y2bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nmi-y2bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:lens-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz-vsrl_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qz-vsrl_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:iris-scan-solid" /></template>

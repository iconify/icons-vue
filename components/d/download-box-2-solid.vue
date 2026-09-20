<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw_ax30_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zw_ax30_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:download-box-2-solid" /></template>

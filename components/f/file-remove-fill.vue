<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrp_fkoog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xrp_fkoog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:file-remove-fill" /></template>

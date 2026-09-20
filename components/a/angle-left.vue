<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdc_khbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdc_khbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:angle-left" /></template>

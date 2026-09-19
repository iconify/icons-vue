<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkbcc_bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bkbcc_bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:check-circle-solid" /></template>

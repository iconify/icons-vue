<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_ipo_afu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o_ipo_afu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:globe" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtg3-_bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtg3-_bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:hospital-symbol" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms-jk-ohc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms-jk-ohc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hwam-4560" /></template>

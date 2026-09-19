<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xec99qfcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xec99qfcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:archive" /></template>

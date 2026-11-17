<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk90i78jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk90i78jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:homey" /></template>

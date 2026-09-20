<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzp1m9bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzp1m9bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:heart-circle3-filled" /></template>

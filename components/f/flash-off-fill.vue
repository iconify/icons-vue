<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laq_aqbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="laq_aqbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:flash-off-fill" /></template>

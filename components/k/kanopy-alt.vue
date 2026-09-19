<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx8kpodkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx8kpodkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:kanopy-alt" /></template>

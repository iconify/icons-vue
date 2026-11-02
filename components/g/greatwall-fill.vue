<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpp256gqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpp256gqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:greatwall-fill" /></template>

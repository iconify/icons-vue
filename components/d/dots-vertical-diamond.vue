<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdmof35ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdmof35ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-vertical-diamond" /></template>

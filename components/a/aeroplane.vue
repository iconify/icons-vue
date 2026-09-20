<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nec4-ibtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nec4-ibtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:aeroplane" /></template>

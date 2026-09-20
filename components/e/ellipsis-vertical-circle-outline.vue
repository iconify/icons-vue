<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrjc3wo0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrjc3wo0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ellipsis-vertical-circle-outline" /></template>

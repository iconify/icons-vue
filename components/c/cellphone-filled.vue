<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxe-cybdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxe-cybdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:cellphone-filled" /></template>

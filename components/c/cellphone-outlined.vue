<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts7a0cbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts7a0cbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:cellphone-outlined" /></template>

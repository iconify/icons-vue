<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qutl96rfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qutl96rfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:litecoin" /></template>

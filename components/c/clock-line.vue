<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjhcxebha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjhcxebha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clock-line" /></template>

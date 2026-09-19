<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjmizab8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjmizab8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:expand-lines" /></template>

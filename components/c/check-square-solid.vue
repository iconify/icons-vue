<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-ttxywqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v-ttxywqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:check-square-solid" /></template>

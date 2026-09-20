<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbjzahddm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbjzahddm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:help-question-network-bold" /></template>

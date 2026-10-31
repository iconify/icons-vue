<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfzeh9bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfzeh9bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-plus-round" /></template>

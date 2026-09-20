<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnilq3uxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnilq3uxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:info-circle-light" /></template>

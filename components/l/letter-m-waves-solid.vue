<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrkhkpb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrkhkpb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-m-waves-solid" /></template>

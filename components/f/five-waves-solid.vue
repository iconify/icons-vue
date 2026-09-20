<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj0xv2bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj0xv2bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:five-waves-solid" /></template>

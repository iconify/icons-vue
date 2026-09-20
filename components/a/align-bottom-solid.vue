<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwxn1vbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwxn1vbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:align-bottom-solid" /></template>

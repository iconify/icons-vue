<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nshhuzb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nshhuzb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-corner-up-left-solid" /></template>

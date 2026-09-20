<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwc5_gbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwc5_gbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:flower" /></template>

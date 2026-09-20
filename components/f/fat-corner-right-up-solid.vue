<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkozqyebv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkozqyebv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-corner-right-up-solid" /></template>

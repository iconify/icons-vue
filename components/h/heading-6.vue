<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3kyahcdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3kyahcdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heading-6" /></template>

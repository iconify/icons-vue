<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4si8vbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4si8vbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-i-circle" /></template>

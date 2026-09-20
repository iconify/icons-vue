<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfghgstxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":24};
const content = `<path class="cfghgstxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:back-filled" /></template>

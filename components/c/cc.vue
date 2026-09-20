<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk07qcbce.css';
import '../../css/c/cyflbfbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk07qcbce"/><path class="cyflbfbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cc" /></template>

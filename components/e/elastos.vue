<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs7-zybgo.css';
import '../../css/h/hwwfh42ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs7-zybgo"/><path class="hwwfh42ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:elastos" /></template>

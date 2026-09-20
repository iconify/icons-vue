<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrwmq7ofm.css';
import '../../css/j/jb0hwxb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrwmq7ofm"/><path clip-rule="evenodd" class="jb0hwxb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:emoji-smile-side" /></template>

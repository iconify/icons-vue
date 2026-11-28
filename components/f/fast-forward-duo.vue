<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yni2ox9wx.css';
import '../../css/r/rr69ofbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary yni2ox9wx"/><path class="primary rr69ofbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:fast-forward-duo" /></template>

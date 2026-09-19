<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf-767cdz.css';
import '../../css/l/lidjc4bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf-767cdz"/><path class="lidjc4bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:future-filled" /></template>

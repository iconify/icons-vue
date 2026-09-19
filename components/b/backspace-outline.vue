<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtkxfz27r.css';
import '../../css/x/xz_jktb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtkxfz27r"/><path clip-rule="evenodd" class="xz_jktb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:backspace-outline" /></template>

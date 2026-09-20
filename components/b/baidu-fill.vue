<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q18y_zbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q18y_zbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:baidu-fill" /></template>

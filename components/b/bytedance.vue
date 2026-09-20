<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qns1zst_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qns1zst_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bytedance" /></template>

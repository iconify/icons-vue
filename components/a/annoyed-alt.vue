<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpuib-bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpuib-bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:annoyed-alt" /></template>

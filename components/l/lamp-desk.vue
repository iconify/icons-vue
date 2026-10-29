<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo488-cjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo488-cjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lamp-desk" /></template>

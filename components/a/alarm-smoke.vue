<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc-bx1btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc-bx1btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:alarm-smoke" /></template>

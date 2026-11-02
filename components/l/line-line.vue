<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyc-bvbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyc-bvbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:line-line" /></template>

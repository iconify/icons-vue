<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qleqgr0-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="qleqgr0-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:backward-square-f" /></template>

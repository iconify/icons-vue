<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yepaq--qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yepaq--qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:direction-up-2" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq27p9txl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq27p9txl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:addydotio" /></template>

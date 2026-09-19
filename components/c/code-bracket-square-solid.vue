<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj89p6enm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yj89p6enm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:code-bracket-square-solid" /></template>

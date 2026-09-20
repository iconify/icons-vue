<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6wuaacbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6wuaacbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:blz" /></template>

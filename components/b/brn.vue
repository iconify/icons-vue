<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3v8b3bbr.css';
import '../../css/o/onhszcbsu.css';
import '../../css/l/lwca995sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3v8b3bbr"/><path class="onhszcbsu"/><path class="lwca995sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:brn" /></template>

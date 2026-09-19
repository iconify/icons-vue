<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxyw-hbts.css';
import '../../css/o/o0pkr5bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxyw-hbts"/><path class="o0pkr5bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:exit" /></template>

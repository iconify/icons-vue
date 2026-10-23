<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9rwxccsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9rwxccsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:cross" /></template>

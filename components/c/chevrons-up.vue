<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5-240xqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5-240xqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chevrons-up" /></template>

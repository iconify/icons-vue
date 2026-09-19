<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txzmh0bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txzmh0bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:folder" /></template>

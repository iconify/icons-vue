<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ootsl4bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ootsl4bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:corner-up-right" /></template>

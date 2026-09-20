<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_hu68j3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_hu68j3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-bar-fill" /></template>

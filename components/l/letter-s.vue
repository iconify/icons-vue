<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr5sb_z4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr5sb_z4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-s" /></template>

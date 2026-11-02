<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmukxqtqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmukxqtqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alarm-clock-minus-fill" /></template>

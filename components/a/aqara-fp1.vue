<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz7do5bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz7do5bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-fp1" /></template>

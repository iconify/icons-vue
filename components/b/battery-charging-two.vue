<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de_jx0dbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de_jx0dbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:battery-charging-two" /></template>

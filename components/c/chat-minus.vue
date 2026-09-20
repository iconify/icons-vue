<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e69msyb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e69msyb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chat-minus" /></template>

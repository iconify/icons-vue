<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxmz9hxtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxmz9hxtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:add2-outlined" /></template>

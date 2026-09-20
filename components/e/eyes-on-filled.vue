<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu7jkfbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu7jkfbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:eyes-on-filled" /></template>

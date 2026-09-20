<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7l4uhbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7l4uhbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:battery-3full-filled" /></template>

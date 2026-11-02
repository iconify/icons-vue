<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkfa4fbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkfa4fbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dress-line" /></template>

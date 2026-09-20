<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz_n9wboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz_n9wboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chat-bubble-help-filled" /></template>

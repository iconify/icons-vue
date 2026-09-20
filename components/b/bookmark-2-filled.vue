<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyabt0bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyabt0bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bookmark-2-filled" /></template>

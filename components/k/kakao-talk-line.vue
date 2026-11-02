<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glq0v05nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glq0v05nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:kakao-talk-line" /></template>

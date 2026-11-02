<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg5ua8opk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg5ua8opk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-check-big-fill" /></template>

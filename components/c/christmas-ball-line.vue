<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmtgx5unr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmtgx5unr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:christmas-ball-line" /></template>

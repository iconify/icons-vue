<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7wj9tb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7wj9tb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:danmaku-off-fill" /></template>

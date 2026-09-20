<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff1o3km4s.css';
import '../../css/s/s3ykwebuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff1o3km4s"/><path class="s3ykwebuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:confused-line" /></template>

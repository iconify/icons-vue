<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uajmqcs3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uajmqcs3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:board-fill" /></template>

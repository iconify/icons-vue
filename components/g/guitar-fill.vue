<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im79o4bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im79o4bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:guitar-fill" /></template>

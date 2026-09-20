<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv7ga9gnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv7ga9gnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bubbles" /></template>

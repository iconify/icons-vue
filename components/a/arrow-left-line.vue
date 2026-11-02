<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r61kq0bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r61kq0bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-left-line" /></template>

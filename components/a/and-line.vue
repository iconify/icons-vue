<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtk7g9bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtk7g9bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:and-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cws1kbczm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cws1kbczm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:american-football-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfizv0bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfizv0bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:football-fill" /></template>

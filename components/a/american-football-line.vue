<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiongsb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wiongsb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:american-football-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/x/xs57kdb9i.css';
import '../../css/h/hzzf7bglq.css';
import '../../css/h/hslk2mt9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="xs57kdb9i"/><path class="hzzf7bglq"/><path class="hslk2mt9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:keyboard" /></template>

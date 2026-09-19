<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz0nrs-zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz0nrs-zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-symphony-t1" /></template>

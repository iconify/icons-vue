<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzo6s_4tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzo6s_4tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dual-sim-1-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tww3lhbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tww3lhbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:check-circle-dash-fill" /></template>

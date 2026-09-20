<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymfmxbbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymfmxbbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chip-fill" /></template>

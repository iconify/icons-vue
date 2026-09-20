<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryydanbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryydanbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:burj-al-arab-line" /></template>

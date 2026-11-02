<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq26mfbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq26mfbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-7-fill" /></template>

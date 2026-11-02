<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx0mq7gqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx0mq7gqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fingerprint-line" /></template>

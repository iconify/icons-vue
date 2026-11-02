<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8p2reb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8p2reb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-equal-fill" /></template>

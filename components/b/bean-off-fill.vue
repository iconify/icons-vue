<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4n1m4bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4n1m4bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bean-off-fill" /></template>

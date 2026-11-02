<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hti6wubho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hti6wubho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:injection-fill" /></template>

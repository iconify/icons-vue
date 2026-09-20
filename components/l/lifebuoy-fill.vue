<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk3didcla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk3didcla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lifebuoy-fill" /></template>

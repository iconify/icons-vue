<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecs7zwxur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecs7zwxur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hail-line" /></template>

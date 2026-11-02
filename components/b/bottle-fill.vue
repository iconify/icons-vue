<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc87yqbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc87yqbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bottle-fill" /></template>

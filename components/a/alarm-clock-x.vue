<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkk5hqbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkk5hqbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:alarm-clock-x" /></template>

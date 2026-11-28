<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvucihbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvucihbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bell-info" /></template>

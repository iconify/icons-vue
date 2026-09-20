<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpi7s0iih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpi7s0iih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-exclamation" /></template>

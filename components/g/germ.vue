<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_t_n4bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_t_n4bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:germ" /></template>

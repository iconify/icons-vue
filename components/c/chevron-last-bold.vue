<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s47kc73dd.css';
import '../../css/q/q2tc4sbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s47kc73dd"/><path class="q2tc4sbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevron-last-bold" /></template>

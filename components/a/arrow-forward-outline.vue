<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_f4g8b1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q_f4g8b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-forward-outline" /></template>

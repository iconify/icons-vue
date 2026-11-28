<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwezv1bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwezv1bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gate-buffer-tri-state-solid" /></template>

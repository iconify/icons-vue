<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw7m7766j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw7m7766j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-narrow-up" /></template>

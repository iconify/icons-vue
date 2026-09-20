<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpd133fzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpd133fzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:corner-up-left" /></template>

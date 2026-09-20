<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s54glg70g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s54glg70g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:door-off" /></template>

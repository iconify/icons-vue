<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6ldn1b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6ldn1b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cloud-off" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll7f9pbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll7f9pbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:airplane" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx8s92bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx8s92bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:forward-big" /></template>

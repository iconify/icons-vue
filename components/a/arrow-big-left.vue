<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dybqn6b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dybqn6b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-big-left" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1a1axb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1a1axb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-long-up" /></template>

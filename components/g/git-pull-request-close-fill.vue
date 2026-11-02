<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uozvk3bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uozvk3bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-pull-request-close-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg0h9qbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg0h9qbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-up-square-solid" /></template>

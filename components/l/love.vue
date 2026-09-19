<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb_q_ubbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="eb_q_ubbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:love" /></template>

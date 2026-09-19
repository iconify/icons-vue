<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5tmslb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5tmslb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dashboard-circle" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e89tq6b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e89tq6b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:laposte" /></template>

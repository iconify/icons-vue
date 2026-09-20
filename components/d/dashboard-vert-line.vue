<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9k9a11_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9k9a11_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:dashboard-vert-line" /></template>

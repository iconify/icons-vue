<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgn7pgbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgn7pgbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-top-line" /></template>

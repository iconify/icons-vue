<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e50bn5bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e50bn5bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:invite-fill" /></template>

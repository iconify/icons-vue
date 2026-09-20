<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m56smtbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m56smtbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flag-2-fill" /></template>

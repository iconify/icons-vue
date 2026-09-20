<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i29sy8rki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i29sy8rki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-up-line" /></template>

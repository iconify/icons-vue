<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-frwh58z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-frwh58z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heavy-snowstorm-line" /></template>

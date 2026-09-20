<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijysev5_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijysev5_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-up-circle-fill" /></template>

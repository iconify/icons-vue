<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2etapz9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2etapz9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alert-diamond-line" /></template>

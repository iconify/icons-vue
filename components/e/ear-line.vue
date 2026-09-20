<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bum_u10rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bum_u10rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ear-line" /></template>

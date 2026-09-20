<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9ex8-brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9ex8-brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clock-square-bold" /></template>

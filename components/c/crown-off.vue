<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td245dbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td245dbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crown-off" /></template>

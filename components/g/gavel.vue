<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu6rl3bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu6rl3bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:gavel" /></template>

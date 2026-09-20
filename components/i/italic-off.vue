<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqzc6h09o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqzc6h09o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:italic-off" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ochnrrb8e.css';
import '../../css/k/kvj5aub-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ochnrrb8e"/><path class="kvj5aub-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:broom-bold" /></template>

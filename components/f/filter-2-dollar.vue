<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evzcsd07d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evzcsd07d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-2-dollar" /></template>

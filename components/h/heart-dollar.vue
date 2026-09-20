<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1987mbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1987mbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:heart-dollar" /></template>

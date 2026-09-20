<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asaafab5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asaafab5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cross-off" /></template>

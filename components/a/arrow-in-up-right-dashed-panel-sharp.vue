<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq_3ltbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq_3ltbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-up-right-dashed-panel-sharp" /></template>

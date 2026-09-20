<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p69jomuhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p69jomuhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-sharp-fill" /></template>

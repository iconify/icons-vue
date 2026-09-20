<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moee6dvip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moee6dvip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-2-sharp" /></template>

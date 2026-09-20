<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfvuhvbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfvuhvbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-area-sharp" /></template>

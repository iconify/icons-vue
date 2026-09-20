<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0a7rtval.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0a7rtval"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bracket-arrow-down-sharp" /></template>

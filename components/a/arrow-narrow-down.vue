<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma9bgvbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma9bgvbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-narrow-down" /></template>

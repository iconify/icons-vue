<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbb1b55bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbb1b55bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-check-sharp" /></template>

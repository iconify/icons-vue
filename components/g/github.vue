<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jduy-2b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jduy-2b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:github" /></template>

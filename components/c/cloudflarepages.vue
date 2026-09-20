<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9z3llz6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9z3llz6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:cloudflarepages" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9_2j3bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9_2j3bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:end-call-bold" /></template>

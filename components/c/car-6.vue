<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_g86w7hz.css';
import '../../css/v/v4k56rbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_g86w7hz"/><path class="v4k56rbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:car-6" /></template>

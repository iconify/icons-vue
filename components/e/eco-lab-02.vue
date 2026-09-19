<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi2abd3jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi2abd3jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:eco-lab-02" /></template>

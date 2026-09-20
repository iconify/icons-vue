<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2c8sk-0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2c8sk-0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:bed-bunk" /></template>

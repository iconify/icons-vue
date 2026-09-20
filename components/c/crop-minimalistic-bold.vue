<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8av0wb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q8av0wb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crop-minimalistic-bold" /></template>

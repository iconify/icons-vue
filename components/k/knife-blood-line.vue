<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1d4eejru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1d4eejru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:knife-blood-line" /></template>

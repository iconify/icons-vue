<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghj_vqn2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ghj_vqn2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbell-small-outline" /></template>

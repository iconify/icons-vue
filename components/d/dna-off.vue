<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j949-8b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j949-8b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dna-off" /></template>

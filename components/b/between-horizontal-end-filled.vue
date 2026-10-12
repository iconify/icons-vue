<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swzmu3awr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swzmu3awr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:between-horizontal-end-filled" /></template>

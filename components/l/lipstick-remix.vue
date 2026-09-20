<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x495w1bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x495w1bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:lipstick-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fixp_fkrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fixp_fkrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:landscape-view-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh9gwwb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rh9gwwb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:close-policy-gaps-alt-outline" /></template>

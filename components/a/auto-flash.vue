<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pisil_48w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pisil_48w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:auto-flash" /></template>

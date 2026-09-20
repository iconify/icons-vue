<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs9y-_bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fs9y-_bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:dashboard-gauge-medium-2-remix" /></template>

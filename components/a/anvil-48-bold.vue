<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x931whbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x931whbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:anvil-48-bold" /></template>

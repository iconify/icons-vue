<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka74e-dqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ka74e-dqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:filter-outline" /></template>

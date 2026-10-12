<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibdu4nf8k.css';
import '../../css/s/s_4tnnghm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ibdu4nf8k"/><path class="s_4tnnghm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dog-48-bold" /></template>

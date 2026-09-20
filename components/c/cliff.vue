<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4seh8bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s4seh8bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:cliff" /></template>

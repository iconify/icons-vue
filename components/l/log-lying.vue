<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip6unyqaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ip6unyqaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:log-lying" /></template>

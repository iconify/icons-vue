<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2ecdnyfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j2ecdnyfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:database" /></template>

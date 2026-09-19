<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmuwebbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nmuwebbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:cucumber" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i08sjibyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i08sjibyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hedgedoc-dark" /></template>

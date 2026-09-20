<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neqtoyb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="neqtoyb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lion" /></template>

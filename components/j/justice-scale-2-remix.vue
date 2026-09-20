<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cslz_9bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cslz_9bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:justice-scale-2-remix" /></template>

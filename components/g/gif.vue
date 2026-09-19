<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s75lp1bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s75lp1bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:gif" /></template>

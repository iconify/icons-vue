<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spgcbb6vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spgcbb6vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-right-3-square-bold" /></template>

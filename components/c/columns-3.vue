<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nie1e_bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nie1e_bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:columns-3" /></template>

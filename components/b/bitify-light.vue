<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fat_n_bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fat_n_bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bitify-light" /></template>

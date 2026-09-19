<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvlhidpax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvlhidpax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bone" /></template>

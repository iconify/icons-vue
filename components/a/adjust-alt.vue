<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqmzj2bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqmzj2bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:adjust-alt" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if3rg7blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="if3rg7blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-star-half" /></template>

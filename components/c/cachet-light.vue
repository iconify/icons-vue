<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0qyrsbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j0qyrsbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cachet-light" /></template>

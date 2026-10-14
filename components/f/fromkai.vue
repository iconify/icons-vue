<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2mrw5btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k2mrw5btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fromkai" /></template>

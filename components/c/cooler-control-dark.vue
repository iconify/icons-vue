<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c90rkqbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c90rkqbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cooler-control-dark" /></template>

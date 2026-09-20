<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr7uzqbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr7uzqbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:arrow-down-left" /></template>

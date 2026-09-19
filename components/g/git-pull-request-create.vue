<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km6do4blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km6do4blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:git-pull-request-create" /></template>

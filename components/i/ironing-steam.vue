<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rae37_bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rae37_bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ironing-steam" /></template>

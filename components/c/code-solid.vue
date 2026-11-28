<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k39ph6bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k39ph6bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:code-solid" /></template>

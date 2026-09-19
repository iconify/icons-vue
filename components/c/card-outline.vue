<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k716ik9pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k716ik9pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:card-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7g7l5bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k7g7l5bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:check-circle-1-fill" /></template>

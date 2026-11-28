<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u40vxjg4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u40vxjg4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:banknote-x" /></template>

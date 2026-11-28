<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfj1x259w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfj1x259w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:files-check" /></template>

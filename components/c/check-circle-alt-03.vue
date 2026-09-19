<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-ohvabme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-ohvabme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:check-circle-alt-03" /></template>

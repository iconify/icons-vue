<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk--bfbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk--bfbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:brain-check" /></template>

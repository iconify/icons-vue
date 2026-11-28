<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg8foxbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg8foxbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:badge-percent-x" /></template>

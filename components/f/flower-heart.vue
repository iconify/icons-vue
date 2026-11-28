<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmtmlwp9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmtmlwp9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:flower-heart" /></template>

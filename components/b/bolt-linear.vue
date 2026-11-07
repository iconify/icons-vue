<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcc74ebsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcc74ebsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bolt-linear" /></template>

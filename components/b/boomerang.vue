<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtrazvdax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtrazvdax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:boomerang" /></template>

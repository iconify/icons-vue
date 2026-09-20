<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6032fbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6032fbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bose" /></template>

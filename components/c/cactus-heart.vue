<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alx5mewnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alx5mewnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cactus-heart" /></template>

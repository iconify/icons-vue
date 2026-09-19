<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smcp5cl5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smcp5cl5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:glasses" /></template>

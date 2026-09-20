<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7uswhbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y7uswhbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fighter-jet-plane" /></template>

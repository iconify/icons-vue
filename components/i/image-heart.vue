<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnzvm5byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnzvm5byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:image-heart" /></template>

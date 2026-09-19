<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcz48-bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lcz48-bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:jigsaw-puzzle" /></template>

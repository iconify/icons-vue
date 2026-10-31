<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aejdy5bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aejdy5bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:door-round" /></template>

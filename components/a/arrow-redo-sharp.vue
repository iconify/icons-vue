<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya4px7blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ya4px7blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-redo-sharp" /></template>

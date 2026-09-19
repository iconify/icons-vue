<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fycv7t8zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fycv7t8zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:inertiajs-wordmark" /></template>

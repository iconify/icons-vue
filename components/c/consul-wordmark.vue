<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6x24cc9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="s6x24cc9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:consul-wordmark" /></template>

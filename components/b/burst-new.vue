<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2dz3rb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="h2dz3rb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:burst-new" /></template>

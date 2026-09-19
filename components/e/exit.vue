<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czfh16-4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="czfh16-4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:exit" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcklqbs9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rcklqbs9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:magnifying-glass-minus-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swbyr0bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swbyr0bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:compiler-explorer" /></template>

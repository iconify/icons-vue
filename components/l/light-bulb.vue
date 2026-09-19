<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acxe7qz5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="acxe7qz5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:light-bulb" /></template>

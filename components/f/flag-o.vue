<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w32e8gb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1728,"height":1536};
const content = `<path class="w32e8gb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:flag-o" /></template>

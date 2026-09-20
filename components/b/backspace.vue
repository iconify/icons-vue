<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp-7lzc2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rp-7lzc2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:backspace" /></template>

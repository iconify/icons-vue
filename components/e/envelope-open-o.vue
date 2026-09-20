<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzzp38b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fzzp38b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:envelope-open-o" /></template>

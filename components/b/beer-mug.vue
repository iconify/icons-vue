<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9sd74bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z9sd74bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:beer-mug" /></template>

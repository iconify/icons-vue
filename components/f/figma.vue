<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wahv08b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wahv08b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:figma" /></template>

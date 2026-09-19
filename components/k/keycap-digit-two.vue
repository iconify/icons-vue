<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwia4_b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jwia4_b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-two" /></template>

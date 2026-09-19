<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_1ewccfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="f_1ewccfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:link-remove-stroke-12" /></template>

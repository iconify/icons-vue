<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb3p8fb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb3p8fb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:laptop-question" /></template>

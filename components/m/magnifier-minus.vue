<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nve8_x58c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nve8_x58c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:magnifier-minus" /></template>

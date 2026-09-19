<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcof_8bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wcof_8bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-ten-small" /></template>

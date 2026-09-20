<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzo9n2i8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mzo9n2i8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cake-slice-remix" /></template>

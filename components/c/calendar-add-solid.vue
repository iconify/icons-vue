<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8-97cbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y8-97cbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:calendar-add-solid" /></template>

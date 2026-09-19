<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvd8j0b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tvd8j0b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:cloud" /></template>

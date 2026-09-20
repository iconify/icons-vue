<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5vgli-7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h5vgli-7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:beer-pitch-solid" /></template>

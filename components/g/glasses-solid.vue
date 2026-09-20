<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofr0nkb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ofr0nkb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:glasses-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0ohrig9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="w0ohrig9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cube-transparent-20-solid" /></template>

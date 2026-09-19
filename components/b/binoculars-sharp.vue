<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji6d9equt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ji6d9equt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:binoculars-sharp" /></template>

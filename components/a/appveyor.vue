<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shr4fu72y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="shr4fu72y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:appveyor" /></template>

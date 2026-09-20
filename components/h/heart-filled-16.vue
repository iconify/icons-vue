<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi4ot5f0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pi4ot5f0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:heart-filled-16" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogmt1ccvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ogmt1ccvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:google-plus-g" /></template>

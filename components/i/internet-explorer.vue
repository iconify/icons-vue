<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdd8rx4on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gdd8rx4on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:internet-explorer" /></template>

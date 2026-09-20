<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0sf03b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z0sf03b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:globe-americas-solid" /></template>

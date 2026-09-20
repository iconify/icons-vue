<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l80mjvbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l80mjvbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:globe-africa-solid" /></template>

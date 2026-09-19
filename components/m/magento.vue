<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilyi3y8_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ilyi3y8_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:magento" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga-2uf8mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="ga-2uf8mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:creative-commons" /></template>

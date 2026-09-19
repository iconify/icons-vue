<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eph5_wbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eph5_wbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:analytica" /></template>

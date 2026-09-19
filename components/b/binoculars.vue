<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teoaifbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="teoaifbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:binoculars" /></template>

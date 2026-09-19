<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9dkbobhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s9dkbobhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:google-plus3" /></template>

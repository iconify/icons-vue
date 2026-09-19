<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syygxic3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="syygxic3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:arpdownup" /></template>

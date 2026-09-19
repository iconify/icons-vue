<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szv6o4bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="szv6o4bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:button-starburst" /></template>

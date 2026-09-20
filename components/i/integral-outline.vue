<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpbunql8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rpbunql8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:integral-outline" /></template>

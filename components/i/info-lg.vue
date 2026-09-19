<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqt0chb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oqt0chb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:info-lg" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4zsyv-to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n4zsyv-to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:cercle-1" /></template>

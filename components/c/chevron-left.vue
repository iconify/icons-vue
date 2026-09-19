<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dajyi23za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dajyi23za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:chevron-left" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_r8l5bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r_r8l5bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:adobe-xd" /></template>

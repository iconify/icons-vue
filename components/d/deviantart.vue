<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk_m1xb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pk_m1xb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:deviantart" /></template>

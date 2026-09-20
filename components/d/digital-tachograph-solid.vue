<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l16sp9c4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l16sp9c4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:digital-tachograph-solid" /></template>

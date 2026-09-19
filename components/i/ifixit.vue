<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hla5t0g8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hla5t0g8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:ifixit" /></template>

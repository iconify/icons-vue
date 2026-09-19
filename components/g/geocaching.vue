<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa4eobcfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pa4eobcfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:geocaching" /></template>

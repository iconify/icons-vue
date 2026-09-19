<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7jmbd1dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o7jmbd1dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:google-plus" /></template>

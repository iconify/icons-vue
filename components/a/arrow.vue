<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiwvheg7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="hiwvheg7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:arrow" /></template>

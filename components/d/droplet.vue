<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9w0jyb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="z9w0jyb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:droplet" /></template>

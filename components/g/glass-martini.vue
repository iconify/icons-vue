<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkski0lic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nkski0lic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:glass-martini" /></template>

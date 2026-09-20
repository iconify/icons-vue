<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgm34ztfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dgm34ztfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dribbble" /></template>

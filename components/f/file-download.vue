<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppzu5_91m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ppzu5_91m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:file-download" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0fu8dkns.css';
import '../../css/y/y66poj2zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="d0fu8dkns"/><path class="y66poj2zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gallery-thumbnails-filled" /></template>

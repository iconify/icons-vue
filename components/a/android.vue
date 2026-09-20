<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfww3p6yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zfww3p6yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:android" /></template>

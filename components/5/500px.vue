<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gftmt4b9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gftmt4b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:500px" /></template>

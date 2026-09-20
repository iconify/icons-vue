<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjcww6b2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pjcww6b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:i-cursor" /></template>

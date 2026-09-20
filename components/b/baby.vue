<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvoikgb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dvoikgb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:baby" /></template>

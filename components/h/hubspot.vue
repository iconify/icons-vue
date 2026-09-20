<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr3evobfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wr3evobfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hubspot" /></template>

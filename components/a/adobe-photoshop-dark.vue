<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_jd-0b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g_jd-0b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-photoshop-dark" /></template>

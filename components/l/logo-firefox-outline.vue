<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3rv87b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h3rv87b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-firefox-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhxtm0v3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uhxtm0v3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:logo-soundcloud-2" /></template>

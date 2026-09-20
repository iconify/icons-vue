<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjpg0ju9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bjpg0ju9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:hammerandscrewdriver" /></template>

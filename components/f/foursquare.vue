<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzck6r5dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":512};
const content = `<path class="bzck6r5dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:foursquare" /></template>

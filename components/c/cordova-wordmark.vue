<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duyp1yy5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="duyp1yy5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:cordova-wordmark" /></template>

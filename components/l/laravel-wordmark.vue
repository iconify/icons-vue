<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3gwl8b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="w3gwl8b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:laravel-wordmark" /></template>

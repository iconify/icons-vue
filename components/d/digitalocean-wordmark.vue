<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wevj32b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wevj32b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:digitalocean-wordmark" /></template>

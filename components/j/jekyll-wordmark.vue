<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oik34rbfa.css';
import '../../css/i/ifrdxluft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="oik34rbfa"/><path class="ifrdxluft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:jekyll-wordmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6l_j5b2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n6l_j5b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:ecto-wordmark" /></template>

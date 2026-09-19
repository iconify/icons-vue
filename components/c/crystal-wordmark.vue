<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmo_f7bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lmo_f7bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:crystal-wordmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n63lptb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="n63lptb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:linkedin-in" /></template>

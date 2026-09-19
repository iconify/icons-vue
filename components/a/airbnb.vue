<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u85wa9_iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="u85wa9_iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:airbnb" /></template>

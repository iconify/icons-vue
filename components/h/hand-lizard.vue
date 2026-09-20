<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjyr4sbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rjyr4sbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hand-lizard" /></template>

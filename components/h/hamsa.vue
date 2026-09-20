<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl6hodhli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fl6hodhli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hamsa" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohee2bcad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ohee2bcad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:log-in" /></template>

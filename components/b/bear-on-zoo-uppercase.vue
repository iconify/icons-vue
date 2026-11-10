<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnigs8hue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tnigs8hue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bear-on-zoo-uppercase" /></template>

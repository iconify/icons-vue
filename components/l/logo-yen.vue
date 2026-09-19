<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4b5wgb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r4b5wgb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-yen" /></template>

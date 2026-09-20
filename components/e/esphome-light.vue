<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3a8ye1ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z3a8ye1ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:esphome-light" /></template>

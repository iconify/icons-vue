<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-fh4lbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="u-fh4lbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:hand-point-up" /></template>

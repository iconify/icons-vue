<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eth3w7x-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eth3w7x-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-xing-outline" /></template>

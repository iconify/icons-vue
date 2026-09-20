<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i44r3pb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i44r3pb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hyperpipe-light" /></template>

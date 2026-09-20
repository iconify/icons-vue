<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuus5rbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fuus5rbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:full-screen-exit" /></template>

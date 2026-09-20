<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhg80cclb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vhg80cclb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:disney-plus-dark" /></template>

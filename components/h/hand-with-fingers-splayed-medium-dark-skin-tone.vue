<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7_5d9ber.css';
import '../../css/a/acwejz0_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="z7_5d9ber"/><path class="acwejz0_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:hand-with-fingers-splayed-medium-dark-skin-tone" /></template>

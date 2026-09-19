<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ard_wpbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ard_wpbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:dharmachakra" /></template>

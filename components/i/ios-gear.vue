<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cry_rhb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cry_rhb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-gear" /></template>

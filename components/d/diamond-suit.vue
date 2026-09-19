<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwju7lbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nwju7lbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:diamond-suit" /></template>

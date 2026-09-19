<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnex464ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gnex464ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:keyboard-chevron-compact-down" /></template>

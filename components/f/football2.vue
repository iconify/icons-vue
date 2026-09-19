<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnqw5pnpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gnqw5pnpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:football2" /></template>

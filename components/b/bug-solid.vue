<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj0q8nbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rj0q8nbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bug-solid" /></template>

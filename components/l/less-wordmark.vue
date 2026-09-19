<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyfgbwb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="kyfgbwb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:less-wordmark" /></template>

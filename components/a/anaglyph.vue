<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu4vl3-ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="eu4vl3-ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:anaglyph" /></template>

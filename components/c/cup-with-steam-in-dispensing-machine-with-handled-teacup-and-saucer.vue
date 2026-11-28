<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vztls8b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vztls8b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cup-with-steam-in-dispensing-machine-with-handled-teacup-and-saucer" /></template>

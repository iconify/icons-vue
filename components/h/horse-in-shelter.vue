<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c351c7shn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c351c7shn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:horse-in-shelter" /></template>

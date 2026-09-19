<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y74p83nwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y74p83nwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:chess-king" /></template>

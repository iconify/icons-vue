<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aocd-lq5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aocd-lq5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:boosty" /></template>

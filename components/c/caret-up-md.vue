<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag2su0b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag2su0b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:caret-up-md" /></template>

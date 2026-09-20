<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml2zg-koh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml2zg-koh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:jameson" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfdli4b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="bfdli4b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:america-football-11" /></template>

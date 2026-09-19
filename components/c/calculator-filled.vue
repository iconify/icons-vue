<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj-14zq7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj-14zq7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:calculator-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oapes-jpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oapes-jpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:giphy" /></template>

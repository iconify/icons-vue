<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp-23kbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp-23kbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:botble-cms" /></template>

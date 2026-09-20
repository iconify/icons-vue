<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo_a-o6cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo_a-o6cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:atandt" /></template>

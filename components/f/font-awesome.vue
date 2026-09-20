<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2chacc0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2chacc0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:font-awesome" /></template>

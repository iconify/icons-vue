<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo79yf13r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo79yf13r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:checkio" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fytw7gbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":655,"height":674};
const content = `<path class="fytw7gbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:google" /></template>

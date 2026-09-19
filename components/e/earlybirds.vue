<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr3a5n0ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hr3a5n0ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:earlybirds" /></template>

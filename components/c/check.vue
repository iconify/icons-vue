<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv5mpac2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cv5mpac2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:check" /></template>

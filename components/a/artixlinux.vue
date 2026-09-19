<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s78w2n1mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="s78w2n1mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:artixlinux" /></template>

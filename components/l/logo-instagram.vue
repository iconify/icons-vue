<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk_t5kymf.css';
import '../../css/m/m1idjh0xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fk_t5kymf"/><path class="m1idjh0xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-instagram" /></template>

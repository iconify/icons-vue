<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcz0i0b6y.css';
import '../../css/b/b3uq48bmq.css';
import '../../css/c/clgcxl7va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fcz0i0b6y"/><path class="b3uq48bmq"/><path class="clgcxl7va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:black-circle" /></template>

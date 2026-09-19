<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/js9qw7okl.css';
import '../../css/e/emn3ltbyq.css';
import '../../css/g/gylysco9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="js9qw7okl"/><path class="emn3ltbyq"/><path class="gylysco9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:chair" /></template>

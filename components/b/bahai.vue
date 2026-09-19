<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m37njk4ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m37njk4ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:bahai" /></template>

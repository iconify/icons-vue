<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7vdw0i-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f7vdw0i-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ecto" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1vv_3bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="z1vv_3bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:capacitor" /></template>

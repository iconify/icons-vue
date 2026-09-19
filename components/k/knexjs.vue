<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgp1tcvai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pgp1tcvai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:knexjs" /></template>

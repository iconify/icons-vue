<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqevwuihn.css';
import '../../css/h/h3y3srhuw.css';
import '../../css/m/m0ny71ltk.css';
import '../../css/d/dpj7zshvp.css';
import '../../css/a/annxhtbvs.css';
import '../../css/y/ypf2-ybrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bqevwuihn"/><path class="h3y3srhuw"/><path class="m0ny71ltk"/><path class="dpj7zshvp"/><path class="annxhtbvs"/><path class="ypf2-ybrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:jwt-wordmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stxidc2sn.css';
import '../../css/w/w1nvnyp9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="stxidc2sn"/><path class="w1nvnyp9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:forgejo-wordmark" /></template>

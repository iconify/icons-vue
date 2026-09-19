<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7v76fbki.css';
import '../../css/u/u-3l03b-a.css';
import '../../css/s/skd9ipjko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z7v76fbki"/><path class="u-3l03b-a"/><path class="skd9ipjko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:hospital" /></template>

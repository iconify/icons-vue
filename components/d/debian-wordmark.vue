<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3ll3kbae.css';
import '../../css/i/iyzk2db_h.css';
import '../../css/i/iwengkb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="t3ll3kbae"/><path class="iyzk2db_h"/><path class="iwengkb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:debian-wordmark" /></template>

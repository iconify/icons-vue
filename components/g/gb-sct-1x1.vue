<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdgac_b5a.css';
import '../../css/b/bf6u4_bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mdgac_b5a"/><path transform="scale(102.4 170.66667)" class="bf6u4_bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:gb-sct-1x1" /></template>

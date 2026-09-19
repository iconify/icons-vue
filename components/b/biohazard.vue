<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhhbmgbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="fhhbmgbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:biohazard" /></template>

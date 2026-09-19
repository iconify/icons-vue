<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fra4ptb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fra4ptb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:deploydog" /></template>

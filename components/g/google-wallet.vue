<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz7b-8bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="gz7b-8bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:google-wallet" /></template>

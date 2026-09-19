<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cix7ll-iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="cix7ll-iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:leanpub" /></template>

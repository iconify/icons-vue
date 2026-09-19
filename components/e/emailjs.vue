<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upn1q9b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="upn1q9b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:emailjs" /></template>

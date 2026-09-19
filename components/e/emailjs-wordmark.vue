<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqraoh7pn.css';
import '../../css/a/a7w15ebva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rqraoh7pn"/><path class="a7w15ebva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:emailjs-wordmark" /></template>

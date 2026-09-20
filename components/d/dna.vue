<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdnfh8bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hdnfh8bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dna" /></template>

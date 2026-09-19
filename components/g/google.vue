<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-kukhd7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":488};
const content = `<path class="g-kukhd7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:google" /></template>

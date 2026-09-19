<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x08vz_rzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x08vz_rzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:list-circle-sharp" /></template>

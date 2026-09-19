<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwlye49zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="jwlye49zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:linkedin-in" /></template>

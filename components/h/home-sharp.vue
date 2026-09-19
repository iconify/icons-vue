<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_q5z8bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_q5z8bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:home-sharp" /></template>

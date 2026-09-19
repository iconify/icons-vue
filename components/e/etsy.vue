<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5u_j6n2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="q5u_j6n2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:etsy" /></template>

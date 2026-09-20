<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4wsr5byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s4wsr5byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:envira" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipt9fhbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ipt9fhbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:arrow-down-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da-5a4b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="da-5a4b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:circle-xmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkhogc02b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkhogc02b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kinsta" /></template>

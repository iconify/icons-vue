<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy37wkf-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":23};
const content = `<path class="wy37wkf-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:afterpay-dark" /></template>

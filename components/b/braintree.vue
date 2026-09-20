<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvmdom3gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvmdom3gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:braintree" /></template>

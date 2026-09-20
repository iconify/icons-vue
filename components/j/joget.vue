<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px74n7bta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="px74n7bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:joget" /></template>

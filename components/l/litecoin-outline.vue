<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1frgq2nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f1frgq2nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:litecoin-outline" /></template>

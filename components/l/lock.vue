<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk9mcoe9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1408};
const content = `<path class="fk9mcoe9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:lock" /></template>

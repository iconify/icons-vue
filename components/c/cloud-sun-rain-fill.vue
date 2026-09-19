<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq7_-sb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="aq7_-sb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-sun-rain-fill" /></template>

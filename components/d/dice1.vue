<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d91382b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d91382b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:dice1" /></template>

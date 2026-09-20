<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqg-d-bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mqg-d-bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:icecream" /></template>

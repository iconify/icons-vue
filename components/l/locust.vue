<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh2z3we9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="vh2z3we9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:locust" /></template>

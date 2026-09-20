<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyi9sg69u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="oyi9sg69u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:escalator" /></template>

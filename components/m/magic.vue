<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvba8ccmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="tvba8ccmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:magic" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfi026obj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hfi026obj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:ethereum" /></template>

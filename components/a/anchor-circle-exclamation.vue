<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8ssn3b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="d8ssn3b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:anchor-circle-exclamation" /></template>

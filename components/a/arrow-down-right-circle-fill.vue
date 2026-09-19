<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwlfl3idl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fwlfl3idl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-down-right-circle-fill" /></template>

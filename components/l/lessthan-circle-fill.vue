<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyx33t-2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vyx33t-2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:lessthan-circle-fill" /></template>

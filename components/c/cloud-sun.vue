<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3ocapbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="x3ocapbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-sun" /></template>

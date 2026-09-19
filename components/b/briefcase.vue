<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqi4pnbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uqi4pnbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:briefcase" /></template>

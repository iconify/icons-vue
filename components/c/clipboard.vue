<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bke5vobio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="bke5vobio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:clipboard" /></template>

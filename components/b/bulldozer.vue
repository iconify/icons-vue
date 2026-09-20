<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n92z6fbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="n92z6fbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bulldozer" /></template>

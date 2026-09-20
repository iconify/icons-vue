<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfs43dbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sfs43dbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:drink-can" /></template>

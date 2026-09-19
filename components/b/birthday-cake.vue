<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew1hd7bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ew1hd7bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:birthday-cake" /></template>

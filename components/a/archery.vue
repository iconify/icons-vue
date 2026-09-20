<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlaikz75a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jlaikz75a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:archery" /></template>

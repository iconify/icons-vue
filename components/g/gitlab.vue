<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2cn_abmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="f2cn_abmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:gitlab" /></template>

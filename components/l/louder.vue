<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hja23dbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hja23dbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:louder" /></template>

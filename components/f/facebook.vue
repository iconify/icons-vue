<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlag4hbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":850};
const content = `<path class="tlag4hbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:facebook" /></template>

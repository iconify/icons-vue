<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izferu_zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":850};
const content = `<path class="izferu_zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:controls" /></template>

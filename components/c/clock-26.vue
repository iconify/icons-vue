<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vly9au3wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="vly9au3wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-26" /></template>

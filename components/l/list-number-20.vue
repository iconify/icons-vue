<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv3ibbcem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lv3ibbcem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:list-number-20" /></template>

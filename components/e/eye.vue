<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so7ecdiom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="so7ecdiom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:eye" /></template>

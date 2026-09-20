<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtpka_b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gtpka_b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:info" /></template>

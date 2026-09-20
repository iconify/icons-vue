<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a35c9ac7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="a35c9ac7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:crossed" /></template>

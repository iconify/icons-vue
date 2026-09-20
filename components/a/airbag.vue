<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_htz5hay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="c_htz5hay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:airbag" /></template>

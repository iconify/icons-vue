<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2nqqvsmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="v2nqqvsmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:gentleman" /></template>

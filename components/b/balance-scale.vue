<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0qt-cc0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2176,"height":1792};
const content = `<path class="d0qt-cc0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:balance-scale" /></template>

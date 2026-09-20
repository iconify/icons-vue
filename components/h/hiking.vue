<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8wfjmkdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="n8wfjmkdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:hiking" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggzcegw8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ggzcegw8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:info-circle-fill-20" /></template>

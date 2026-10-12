<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng6032t4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ng6032t4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bubble-check-fill-20" /></template>

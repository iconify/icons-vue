<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5sc-_b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s5sc-_b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-box-left-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti8yumbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ti8yumbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-center-20" /></template>

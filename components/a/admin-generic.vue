<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu3898bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tu3898bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:admin-generic" /></template>

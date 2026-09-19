<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks2y7_bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ks2y7_bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:grid-circle-fill" /></template>

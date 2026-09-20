<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoas7vbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zoas7vbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:book-with-balance-scales" /></template>

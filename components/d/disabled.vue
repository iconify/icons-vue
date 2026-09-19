<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdhhz2seu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="kdhhz2seu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:disabled" /></template>

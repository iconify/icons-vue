<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkov3hnmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bkov3hnmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:chef" /></template>

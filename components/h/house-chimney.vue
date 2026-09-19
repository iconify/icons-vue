<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyesi4bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="lyesi4bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:house-chimney" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkgito_qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jkgito_qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:arrow-down-alt" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_ruc1bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="n_ruc1bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:chevron-right-12" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9gpahb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n9gpahb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-bangladeshi-16-solid" /></template>

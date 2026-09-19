<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-l4m5bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="n-l4m5bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:key-20-solid" /></template>

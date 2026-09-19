<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkr_blxgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hkr_blxgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-long-right-20-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsbzt18rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wsbzt18rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-pound-20-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0-afgbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="y0-afgbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:battery-0-20-solid" /></template>

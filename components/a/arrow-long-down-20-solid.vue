<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq3duqbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wq3duqbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-long-down-20-solid" /></template>

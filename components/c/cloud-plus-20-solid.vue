<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfregu8ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xfregu8ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-plus-20-solid" /></template>

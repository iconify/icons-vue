<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bquigi8rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-7.5};
const content = `<path class="bquigi8rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:ebay" /></template>

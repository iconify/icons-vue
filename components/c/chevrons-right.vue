<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpy5q3b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="tpy5q3b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevrons-right" /></template>

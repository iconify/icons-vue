<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5rzl_u5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5rzl_u5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:coins-stack-solid" /></template>

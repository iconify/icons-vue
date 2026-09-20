<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw547ccnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw547ccnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:call" /></template>

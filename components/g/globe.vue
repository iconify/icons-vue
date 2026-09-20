<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qedv1cb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qedv1cb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:globe" /></template>

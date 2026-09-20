<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjc_0ibxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjc_0ibxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chevron-right" /></template>

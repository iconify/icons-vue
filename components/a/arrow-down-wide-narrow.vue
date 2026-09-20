<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p06wigbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p06wigbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-wide-narrow" /></template>

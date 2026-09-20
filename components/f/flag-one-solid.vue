<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6f1htxrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6f1htxrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:flag-one-solid" /></template>

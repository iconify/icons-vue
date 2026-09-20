<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zie6h6bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zie6h6bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:danger-triangle-solid" /></template>

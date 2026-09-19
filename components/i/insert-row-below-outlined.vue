<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oui3apb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oui3apb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:insert-row-below-outlined" /></template>

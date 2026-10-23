<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djb7u20ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djb7u20ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:component" /></template>

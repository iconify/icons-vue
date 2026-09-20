<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_2l1bbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m_2l1bbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:cursor-text" /></template>

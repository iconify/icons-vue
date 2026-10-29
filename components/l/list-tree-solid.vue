<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl3j3lu6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl3j3lu6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-tree-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v25f94bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v25f94bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-end" /></template>

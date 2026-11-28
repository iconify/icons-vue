<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt17-0bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zt17-0bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-plus-duotone" /></template>

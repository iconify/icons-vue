<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_rm2k5zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_rm2k5zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-gear" /></template>

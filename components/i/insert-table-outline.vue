<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj5mojb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj5mojb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:insert-table-outline" /></template>

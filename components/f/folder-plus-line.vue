<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouaz_3bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ouaz_3bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:folder-plus-line" /></template>

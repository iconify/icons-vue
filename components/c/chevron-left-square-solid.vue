<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_52p3bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_52p3bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-left-square-solid" /></template>

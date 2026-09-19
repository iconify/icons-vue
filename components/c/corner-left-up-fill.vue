<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_4187b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_4187b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:corner-left-up-fill" /></template>

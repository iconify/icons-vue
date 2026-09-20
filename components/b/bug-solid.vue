<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7pa4eh1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v7pa4eh1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bug-solid" /></template>

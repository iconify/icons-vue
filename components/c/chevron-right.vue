<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c791wyter.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c791wyter"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chevron-right" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy-5eub4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uy-5eub4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:circle-x-fill" /></template>

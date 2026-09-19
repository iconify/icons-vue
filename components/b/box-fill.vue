<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv8wbjnnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tv8wbjnnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:box-fill" /></template>

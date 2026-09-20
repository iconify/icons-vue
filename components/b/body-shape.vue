<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7mu9cjrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y7mu9cjrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:body-shape" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-xkbac8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d-xkbac8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:align-h-center" /></template>

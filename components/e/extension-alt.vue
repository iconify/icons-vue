<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaed-9bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yaed-9bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:extension-alt" /></template>

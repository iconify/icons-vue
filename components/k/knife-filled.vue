<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytcuhdbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytcuhdbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:knife-filled" /></template>

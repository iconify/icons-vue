<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx3zk3vyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hx3zk3vyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-left-outline" /></template>

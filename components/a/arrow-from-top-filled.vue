<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx5wrxbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx5wrxbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-from-top-filled" /></template>

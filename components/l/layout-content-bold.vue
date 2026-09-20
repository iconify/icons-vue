<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsg4_cbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zsg4_cbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:layout-content-bold" /></template>

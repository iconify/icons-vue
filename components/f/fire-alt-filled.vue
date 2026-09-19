<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxmcy1bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxmcy1bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fire-alt-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cosbr_2hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cosbr_2hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:lock-off-fill" /></template>

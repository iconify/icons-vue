<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmzwyb1sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmzwyb1sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:apartment-filled" /></template>

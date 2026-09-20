<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3602zgmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3602zgmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:info-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hou_otb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hou_otb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:brand-apple" /></template>

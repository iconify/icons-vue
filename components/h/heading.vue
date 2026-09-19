<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0w5cdeww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0w5cdeww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:heading" /></template>

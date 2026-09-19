<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdty80bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdty80bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:laptop-add" /></template>

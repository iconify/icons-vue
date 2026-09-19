<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0_-0zbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0_-0zbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:edit-off-04" /></template>

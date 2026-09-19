<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpdcibapj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpdcibapj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cursor-edit-01" /></template>

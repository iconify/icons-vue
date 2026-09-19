<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bry5691pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bry5691pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-3-square-fill" /></template>

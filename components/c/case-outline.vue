<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aia290iyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aia290iyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:case-outline" /></template>

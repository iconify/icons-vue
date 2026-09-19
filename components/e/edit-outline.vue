<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfz7cxbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfz7cxbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:edit-outline" /></template>

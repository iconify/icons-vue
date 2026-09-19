<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz1lfe28c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lz1lfe28c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:export" /></template>

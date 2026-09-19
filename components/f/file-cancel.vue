<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr6w8qb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lr6w8qb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file-cancel" /></template>

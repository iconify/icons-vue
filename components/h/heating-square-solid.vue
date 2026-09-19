<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e22xqcbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e22xqcbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:heating-square-solid" /></template>

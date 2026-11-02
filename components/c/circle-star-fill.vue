<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdo4z7ozv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdo4z7ozv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-star-fill" /></template>

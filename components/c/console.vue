<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8moopj2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b8moopj2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:console" /></template>

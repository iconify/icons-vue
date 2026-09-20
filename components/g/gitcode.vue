<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd1fl0qyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd1fl0qyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gitcode" /></template>

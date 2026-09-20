<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8zgv-btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8zgv-btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-remove" /></template>

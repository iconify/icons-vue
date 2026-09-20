<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydmna9bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydmna9bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:items-grid-24" /></template>

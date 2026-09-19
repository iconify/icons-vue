<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbqe6cbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hbqe6cbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:close-square-fill" /></template>

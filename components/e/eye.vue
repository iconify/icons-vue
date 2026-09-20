<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goy4ui_6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="goy4ui_6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:eye" /></template>

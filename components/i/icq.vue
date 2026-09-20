<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4i8jt03t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4i8jt03t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:icq" /></template>

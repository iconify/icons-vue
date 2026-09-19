<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcl2hxb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tcl2hxb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:heart-rate-outline" /></template>

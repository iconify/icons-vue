<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbplu9bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbplu9bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gnome-terminal" /></template>

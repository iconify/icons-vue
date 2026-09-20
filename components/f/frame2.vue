<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm80i3cgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm80i3cgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:frame2" /></template>

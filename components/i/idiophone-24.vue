<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd9tkcbou.css';
import '../../css/g/gwgec4uya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yd9tkcbou"/><path class="gwgec4uya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:idiophone-24" /></template>
